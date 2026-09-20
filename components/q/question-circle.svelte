<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3m_32d1b.css';
import '../../css/m/mvqkmbccf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3m_32d1b"/><path class="mvqkmbccf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:question-circle" {...props}></Icon>
