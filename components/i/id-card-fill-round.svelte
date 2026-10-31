<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/volfzd5cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="volfzd5cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:id-card-fill-round" {...props}></Icon>
