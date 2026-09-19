<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5nzkvbsa.css';
import '../../css/b/bhztshb0g.css';
import '../../css/n/n1mj_5hgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o5nzkvbsa"/><path class="bhztshb0g"/><path class="n1mj_5hgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fund-view" {...props}></Icon>
