<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qorkjt7op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qorkjt7op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:roots-sage" {...props}></Icon>
