<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt0e6jbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt0e6jbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bulma" {...props}></Icon>
