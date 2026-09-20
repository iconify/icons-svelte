<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj6fqqbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj6fqqbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:move-line" {...props}></Icon>
