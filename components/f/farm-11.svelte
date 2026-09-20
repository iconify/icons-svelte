<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ammq8ggrp.css';
import '../../css/n/nss1utbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ammq8ggrp"/><path class="nss1utbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:farm-11" {...props}></Icon>
