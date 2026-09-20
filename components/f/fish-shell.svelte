<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdw7n2bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdw7n2bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fish-shell" {...props}></Icon>
