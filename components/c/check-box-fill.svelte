<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz-3kdwdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hz-3kdwdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:check-box-fill" {...props}></Icon>
