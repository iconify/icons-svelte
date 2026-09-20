<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1e7tlb4k.css';
import '../../css/y/yse77p9vi.css';
import '../../css/v/v-ftc0wtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g1e7tlb4k"/><path class="yse77p9vi"/><path class="v-ftc0wtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-layers" {...props}></Icon>
