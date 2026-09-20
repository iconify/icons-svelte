<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka2syl1pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka2syl1pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codecov-logo" {...props}></Icon>
