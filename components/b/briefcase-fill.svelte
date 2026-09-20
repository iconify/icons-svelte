<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac95nibab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ac95nibab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:briefcase-fill" {...props}></Icon>
