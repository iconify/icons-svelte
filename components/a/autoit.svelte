<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrkrr4jyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrkrr4jyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:autoit" {...props}></Icon>
