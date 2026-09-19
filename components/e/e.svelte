<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kge5ed0vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":406,"height":512};
const content = `<path class="kge5ed0vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:e" {...props}></Icon>
