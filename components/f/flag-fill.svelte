<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu-vi5btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu-vi5btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:flag-fill" {...props}></Icon>
