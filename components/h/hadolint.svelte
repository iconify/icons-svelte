<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzr61tbtm.css';
import '../../css/d/d-6vdibyb.css';
import '../../css/y/yb06lccjp.css';
import '../../css/t/tcn-xl5yi.css';
import '../../css/x/xiamkcxub.css';
import '../../css/y/yqfxoj6jk.css';
import '../../css/h/h53c51bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jzr61tbtm"/><path class="d-6vdibyb"/><path class="yb06lccjp"/><path class="tcn-xl5yi"/><path class="xiamkcxub"/><path class="yqfxoj6jk"/><path class="h53c51bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hadolint" {...props}></Icon>
