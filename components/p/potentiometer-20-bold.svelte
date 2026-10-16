<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmefhab7f.css';
import '../../css/l/lw7snlb5i.css';
import '../../css/k/kh901leqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mmefhab7f"/><path class="lw7snlb5i"/><path class="kh901leqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:potentiometer-20-bold" {...props}></Icon>
