<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tykflebtg.css';
import '../../css/c/cfkeagz0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tykflebtg"/><path class="cfkeagz0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bell-off-filled" {...props}></Icon>
