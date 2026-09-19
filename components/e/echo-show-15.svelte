<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlg_s-bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlg_s-bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-show-15" {...props}></Icon>
