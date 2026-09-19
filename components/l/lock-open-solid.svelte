<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn3lrh4wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn3lrh4wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lock-open-solid" {...props}></Icon>
