<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa0d8lorg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa0d8lorg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-expressionless-fill" {...props}></Icon>
