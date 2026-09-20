<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6q3l21jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6q3l21jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-sharp-fill" {...props}></Icon>
