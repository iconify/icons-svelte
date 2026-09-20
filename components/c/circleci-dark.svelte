<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcovqmb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcovqmb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:circleci-dark" {...props}></Icon>
