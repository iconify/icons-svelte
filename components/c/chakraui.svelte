<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ernn07bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ernn07bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:chakraui" {...props}></Icon>
