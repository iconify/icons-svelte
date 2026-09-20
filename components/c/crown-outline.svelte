<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os9ts92df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="os9ts92df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-outline" {...props}></Icon>
