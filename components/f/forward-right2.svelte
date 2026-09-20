<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw-7h4bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kw-7h4bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forward-right2" {...props}></Icon>
