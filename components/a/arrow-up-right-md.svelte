<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzt9n_bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzt9n_bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-up-right-md" {...props}></Icon>
