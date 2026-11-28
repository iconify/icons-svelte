<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bea9fbhpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bea9fbhpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:layout-list-plus" {...props}></Icon>
