<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8s1zbbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e8s1zbbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-edit" {...props}></Icon>
