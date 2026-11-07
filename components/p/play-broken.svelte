<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy096x3fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy096x3fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-broken" {...props}></Icon>
