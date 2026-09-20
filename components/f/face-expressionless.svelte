<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eanpit8oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eanpit8oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-expressionless" {...props}></Icon>
