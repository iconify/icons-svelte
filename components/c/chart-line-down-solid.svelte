<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_tky7bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_tky7bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chart-line-down-solid" {...props}></Icon>
