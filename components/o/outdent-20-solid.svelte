<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p477_fbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p477_fbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:outdent-20-solid" {...props}></Icon>
