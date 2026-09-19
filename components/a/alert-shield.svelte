<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m747jmphf.css';
import '../../css/x/x7e247bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m747jmphf"/><path class="x7e247bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alert-shield" {...props}></Icon>
