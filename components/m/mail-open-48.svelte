<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_8ipno6c.css';
import '../../css/i/iaquidtow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_8ipno6c"/><path class="iaquidtow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-open-48" {...props}></Icon>
