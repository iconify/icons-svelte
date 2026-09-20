<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9t_v-bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9t_v-bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nasa" {...props}></Icon>
