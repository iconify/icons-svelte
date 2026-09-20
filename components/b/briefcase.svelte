<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcawkrxhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcawkrxhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:briefcase" {...props}></Icon>
