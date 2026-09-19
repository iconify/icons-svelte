<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm-zazo7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sm-zazo7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mana" {...props}></Icon>
