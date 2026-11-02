<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7oqb1ody.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7oqb1ody"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:asterisk-fill" {...props}></Icon>
