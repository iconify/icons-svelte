<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apdbvacmy.css';
import '../../css/u/u_m41fbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="apdbvacmy"/><path class="u_m41fbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:book-bookmark-bold" {...props}></Icon>
