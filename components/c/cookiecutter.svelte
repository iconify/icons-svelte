<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfwb0aceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfwb0aceo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cookiecutter" {...props}></Icon>
