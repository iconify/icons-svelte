<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyddhdbvg.css';
import '../../css/y/yr5bhhobf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wyddhdbvg"/><path class="yr5bhhobf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:play-circle" {...props}></Icon>
