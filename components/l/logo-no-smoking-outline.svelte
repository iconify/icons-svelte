<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8e288bnc.css';
import '../../css/u/un6ua_l-y.css';
import '../../css/v/v4sg5jbkh.css';
import '../../css/z/zlv3p35br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v8e288bnc"/><path class="un6ua_l-y"/><path class="v4sg5jbkh"/><path class="zlv3p35br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-no-smoking-outline" {...props}></Icon>
