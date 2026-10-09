<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw4336b9k.css';
import '../../css/p/phnyk0rqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tw4336b9k"/><path class="phnyk0rqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bbq-48" {...props}></Icon>
