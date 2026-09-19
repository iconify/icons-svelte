<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4p62tssf.css';
import '../../css/h/hvsefo_2t.css';
import '../../css/q/qo_dlfbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4p62tssf"/><path class="hvsefo_2t"/><path class="qo_dlfbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:8-ball" {...props}></Icon>
