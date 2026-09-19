<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il7qhmbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il7qhmbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-triangle-down-fill" {...props}></Icon>
