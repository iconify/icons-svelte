<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfy9qtb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfy9qtb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cardmarket" {...props}></Icon>
