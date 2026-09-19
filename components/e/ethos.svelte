<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujbvu5b5g.css';
import '../../css/o/omc5y5yrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ujbvu5b5g"/><path class="omc5y5yrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ethos" {...props}></Icon>
