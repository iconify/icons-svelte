<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-a338bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-a338bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:female-outline-24px" {...props}></Icon>
