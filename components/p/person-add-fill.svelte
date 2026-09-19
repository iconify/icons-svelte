<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgbqm5b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgbqm5b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:person-add-fill" {...props}></Icon>
