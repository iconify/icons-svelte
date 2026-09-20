<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/civh5k3ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="civh5k3ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hedera" {...props}></Icon>
