<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lloebebob.css';
import '../../css/g/gwm-eyb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lloebebob"/><path class="gwm-eyb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-up-bold-duotone" {...props}></Icon>
