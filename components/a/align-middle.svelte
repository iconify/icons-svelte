<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okr4xubys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okr4xubys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:align-middle" {...props}></Icon>
