<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5bxur4ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5bxur4ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:between-vertical-end" {...props}></Icon>
