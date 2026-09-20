<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0pbqqbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0pbqqbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:italic-24" {...props}></Icon>
