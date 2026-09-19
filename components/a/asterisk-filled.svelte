<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn9-9y8lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn9-9y8lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:asterisk-filled" {...props}></Icon>
