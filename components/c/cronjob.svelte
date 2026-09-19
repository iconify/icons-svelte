<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdb6-6b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdb6-6b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cronjob" {...props}></Icon>
