<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk7r_jbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zk7r_jbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adult" {...props}></Icon>
