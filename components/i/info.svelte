<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/i/ihm8nebko.css';
import '../../css/q/qu79thbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><circle class="ihm8nebko"/><path class="qu79thbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:info" {...props}></Icon>
