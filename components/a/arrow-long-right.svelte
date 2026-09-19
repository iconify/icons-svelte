<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqq-s5bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqq-s5bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-long-right" {...props}></Icon>
