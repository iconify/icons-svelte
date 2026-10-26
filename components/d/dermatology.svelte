<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk4-6obph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lk4-6obph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dermatology" {...props}></Icon>
