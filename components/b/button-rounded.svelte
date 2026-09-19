<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6idjfb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6idjfb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:button-rounded" {...props}></Icon>
