<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s62kcabep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s62kcabep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-2-sharp" {...props}></Icon>
