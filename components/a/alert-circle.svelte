<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj_biz8vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj_biz8vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alert-circle" {...props}></Icon>
