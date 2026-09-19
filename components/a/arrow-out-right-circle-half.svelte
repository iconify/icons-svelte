<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c852q-rbq.css';
import '../../css/z/z7ybbhltq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c852q-rbq"/><path class="z7ybbhltq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-right-circle-half" {...props}></Icon>
