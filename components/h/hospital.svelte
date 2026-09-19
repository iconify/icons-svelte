<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb72zx0al.css';
import '../../css/h/hf-vc2b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb72zx0al"/><path class="hf-vc2b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hospital" {...props}></Icon>
