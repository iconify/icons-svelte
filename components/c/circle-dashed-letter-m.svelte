<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn_jkz6ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_jkz6ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-m" {...props}></Icon>
