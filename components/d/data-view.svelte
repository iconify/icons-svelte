<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmhddevn.css';
import '../../css/u/ueg81y61d.css';
import '../../css/n/neag2rbvc.css';
import '../../css/u/uqlamj4tr.css';
import '../../css/b/bejlyabet.css';
import '../../css/x/xtvj63buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="lgmhddevn"/><path class="ueg81y61d"/><circle class="neag2rbvc"/><circle class="uqlamj4tr"/><circle class="bejlyabet"/><path class="xtvj63buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-view" {...props}></Icon>
