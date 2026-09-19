<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho624zber.css';
import '../../css/a/adot17bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho624zber"/><path class="adot17bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:radio-circle-marked" {...props}></Icon>
