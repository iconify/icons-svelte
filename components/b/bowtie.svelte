<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me8xx5esy.css';
import '../../css/y/yyqg3mbar.css';
import '../../css/o/oh2rpjbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="me8xx5esy"/><path class="yyqg3mbar"/><path class="oh2rpjbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bowtie" {...props}></Icon>
