<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljml8obff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljml8obff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:factory-2-fill" {...props}></Icon>
