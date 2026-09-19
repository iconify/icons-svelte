<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddphdubhq.css';
import '../../css/v/v_8_2yi8g.css';
import '../../css/b/b93e90bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ddphdubhq"/><path class="v_8_2yi8g"/><path class="b93e90bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drill-back" {...props}></Icon>
