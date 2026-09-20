<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq-jsy6wg.css';
import '../../css/d/dqwchbbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq-jsy6wg"/><path class="dqwchbbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:analysis" {...props}></Icon>
