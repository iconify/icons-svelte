<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8e42ccqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o8e42ccqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hira-filled" {...props}></Icon>
