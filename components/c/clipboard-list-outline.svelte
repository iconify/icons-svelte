<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylzevwbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylzevwbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-list-outline" {...props}></Icon>
