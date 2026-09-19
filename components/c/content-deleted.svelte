<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4spwt7oj.css';
import '../../css/u/utvngb1dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4spwt7oj"/><path class="utvngb1dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:content-deleted" {...props}></Icon>
