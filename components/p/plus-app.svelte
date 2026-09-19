<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5vm1ymhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q5vm1ymhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:plus-app" {...props}></Icon>
