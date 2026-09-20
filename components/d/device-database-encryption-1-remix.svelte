<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-9otgbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j-9otgbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:device-database-encryption-1-remix" {...props}></Icon>
