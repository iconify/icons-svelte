<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzvr72bgj.css';
import '../../css/b/bn3wwcchr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mzvr72bgj"/><path class="bn3wwcchr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-20" {...props}></Icon>
