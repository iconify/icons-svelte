<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkhmj7e-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkhmj7e-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:archive-box-arrow-up-solid" {...props}></Icon>
