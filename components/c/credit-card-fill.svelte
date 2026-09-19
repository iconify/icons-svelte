<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6mtzcc9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6mtzcc9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:credit-card-fill" {...props}></Icon>
