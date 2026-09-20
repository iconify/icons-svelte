<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5n3svmjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5n3svmjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-cafe-to-go-outline" {...props}></Icon>
