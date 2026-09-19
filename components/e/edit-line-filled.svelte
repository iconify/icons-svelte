<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yioxj7y0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yioxj7y0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:edit-line-filled" {...props}></Icon>
