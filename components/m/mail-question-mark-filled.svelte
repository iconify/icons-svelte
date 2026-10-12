<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foq2a6bdh.css';
import '../../css/m/mp780dcuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foq2a6bdh"/><path class="mp780dcuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-question-mark-filled" {...props}></Icon>
