<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8a918fho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8a918fho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cd-broken-bold" {...props}></Icon>
