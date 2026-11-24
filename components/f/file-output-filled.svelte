<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaxmjgbje.css';
import '../../css/e/eqpz_zlhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxmjgbje"/><path class="eqpz_zlhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-output-filled" {...props}></Icon>
