<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6p8koql.css';
import '../../css/m/m_pzdih5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj6p8koql"/><path class="m_pzdih5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:opul" {...props}></Icon>
