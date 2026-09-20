<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfnhi005r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfnhi005r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:loader-sharp-fill" {...props}></Icon>
