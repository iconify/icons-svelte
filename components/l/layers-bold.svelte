<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo0l9j9lh.css';
import '../../css/n/nk-dx3faz.css';
import '../../css/q/ql2i1fbyo.css';
import '../../css/e/eusfa-1-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo0l9j9lh"/><path clip-rule="evenodd" class="nk-dx3faz"/><path class="ql2i1fbyo"/><path class="eusfa-1-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layers-bold" {...props}></Icon>
