<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci-c0yb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci-c0yb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-trans" {...props}></Icon>
