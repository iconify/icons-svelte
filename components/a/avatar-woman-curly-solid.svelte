<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v73kcqc0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v73kcqc0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-woman-curly-solid" {...props}></Icon>
