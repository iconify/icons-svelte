<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeiyfybvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeiyfybvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:package" {...props}></Icon>
