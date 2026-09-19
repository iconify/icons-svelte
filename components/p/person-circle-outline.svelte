<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfdi-4buo.css';
import '../../css/t/tk4wqivch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfdi-4buo"/><path class="tk4wqivch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:person-circle-outline" {...props}></Icon>
