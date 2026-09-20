<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6anfqb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6anfqb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-12-sharp-fill" {...props}></Icon>
