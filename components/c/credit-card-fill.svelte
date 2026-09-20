<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toh8bgboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="toh8bgboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:credit-card-fill" {...props}></Icon>
