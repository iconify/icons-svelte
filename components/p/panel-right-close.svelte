<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/a_50g-srm.css';
import '../../css/l/larv589oa.css';
import '../../css/w/wwsorabjx.css';
import '../../css/c/cd5tcvbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="a_50g-srm wm-shadow"/><path class="larv589oa wm-shadow"/><path class="wwsorabjx"/><path class="cd5tcvbln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:panel-right-close" {...props}></Icon>
