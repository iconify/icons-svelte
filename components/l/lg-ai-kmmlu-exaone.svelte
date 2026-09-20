<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udcb4db1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udcb4db1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lg-ai-kmmlu-exaone" {...props}></Icon>
