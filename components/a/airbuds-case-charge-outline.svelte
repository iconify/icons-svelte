<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhimr1abp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhimr1abp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-case-charge-outline" {...props}></Icon>
