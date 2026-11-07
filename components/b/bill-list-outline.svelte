<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhw7bfbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhw7bfbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-list-outline" {...props}></Icon>
