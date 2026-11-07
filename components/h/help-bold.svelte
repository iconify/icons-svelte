<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw5g050oe.css';
import '../../css/w/w19abnbit.css';
import '../../css/t/tsguwswfn.css';
import '../../css/a/ae2knfujf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw5g050oe"/><path class="w19abnbit"/><path class="tsguwswfn"/><path class="ae2knfujf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:help-bold" {...props}></Icon>
