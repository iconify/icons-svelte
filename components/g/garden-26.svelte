<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrgynsbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="qrgynsbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:garden-26" {...props}></Icon>
