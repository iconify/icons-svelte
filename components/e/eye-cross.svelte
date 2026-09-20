<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwoo8gbut.css';
import '../../css/t/t5xij2brj.css';
import '../../css/y/y8jo2vbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwoo8gbut"/><path class="t5xij2brj"/><path class="y8jo2vbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:eye-cross" {...props}></Icon>
