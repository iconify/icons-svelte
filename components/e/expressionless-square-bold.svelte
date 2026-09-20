<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlkqo4fwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xlkqo4fwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:expressionless-square-bold" {...props}></Icon>
